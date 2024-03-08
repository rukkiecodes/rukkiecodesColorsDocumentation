<template>
    <h3 class="mt-10">Pink</h3>
    <v-table>
        <thead>
            <tr>
                <th class="text-left">
                    Name
                </th>
                <th class="text-left">
                    Code
                </th>
                <th class="text-left">
                    Sample
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>{{ pink50.name }}</td>
                <td>{{ pink50.hex }}</td>
                <td>
                    <v-sheet :color="pink50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink100.name }}</td>
                <td>{{ pink100.hex }}</td>
                <td>
                    <v-sheet :color="pink100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink200.name }}</td>
                <td>{{ pink200.hex }}</td>
                <td>
                    <v-sheet :color="pink200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink300.name }}</td>
                <td>{{ pink300.hex }}</td>
                <td>
                    <v-sheet :color="pink300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink400.name }}</td>
                <td>{{ pink400.hex }}</td>
                <td>
                    <v-sheet :color="pink400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink500.name }}</td>
                <td>{{ pink500.hex }}</td>
                <td>
                    <v-sheet :color="pink500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink600.name }}</td>
                <td>{{ pink600.hex }}</td>
                <td>
                    <v-sheet :color="pink600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink700.name }}</td>
                <td>{{ pink700.hex }}</td>
                <td>
                    <v-sheet :color="pink700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink800.name }}</td>
                <td>{{ pink800.hex }}</td>
                <td>
                    <v-sheet :color="pink800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ pink900.name }}</td>
                <td>{{ pink900.hex }}</td>
                <td>
                    <v-sheet :color="pink900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    pink50,
    pink100,
    pink200,
    pink300,
    pink400,
    pink500,
    pink600,
    pink700,
    pink800,
    pink900,
} from 'rukkiecodes-colors';
</script>
