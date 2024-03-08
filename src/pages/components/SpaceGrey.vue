<template>
    <h3 class="mt-10">Space Grey</h3>
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
                <td>{{ spaceGrey50.name }}</td>
                <td>{{ spaceGrey50.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey100.name }}</td>
                <td>{{ spaceGrey100.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey200.name }}</td>
                <td>{{ spaceGrey200.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey300.name }}</td>
                <td>{{ spaceGrey300.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey400.name }}</td>
                <td>{{ spaceGrey400.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey500.name }}</td>
                <td>{{ spaceGrey500.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey600.name }}</td>
                <td>{{ spaceGrey600.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey700.name }}</td>
                <td>{{ spaceGrey700.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey800.name }}</td>
                <td>{{ spaceGrey800.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ spaceGrey900.name }}</td>
                <td>{{ spaceGrey900.hex }}</td>
                <td>
                    <v-sheet :color="spaceGrey900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    spaceGrey50,
    spaceGrey100,
    spaceGrey200,
    spaceGrey300,
    spaceGrey400,
    spaceGrey500,
    spaceGrey600,
    spaceGrey700,
    spaceGrey800,
    spaceGrey900,
} from 'rukkiecodes-colors';
</script>
