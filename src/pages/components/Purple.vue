<template>
    <h3 class="mt-10">Purple</h3>
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
                <td>{{ purple50.name }}</td>
                <td>{{ purple50.hex }}</td>
                <td>
                    <v-sheet :color="purple50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple100.name }}</td>
                <td>{{ purple100.hex }}</td>
                <td>
                    <v-sheet :color="purple100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple200.name }}</td>
                <td>{{ purple200.hex }}</td>
                <td>
                    <v-sheet :color="purple200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple300.name }}</td>
                <td>{{ purple300.hex }}</td>
                <td>
                    <v-sheet :color="purple300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple400.name }}</td>
                <td>{{ purple400.hex }}</td>
                <td>
                    <v-sheet :color="purple400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple500.name }}</td>
                <td>{{ purple500.hex }}</td>
                <td>
                    <v-sheet :color="purple500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple600.name }}</td>
                <td>{{ purple600.hex }}</td>
                <td>
                    <v-sheet :color="purple600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple700.name }}</td>
                <td>{{ purple700.hex }}</td>
                <td>
                    <v-sheet :color="purple700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple800.name }}</td>
                <td>{{ purple800.hex }}</td>
                <td>
                    <v-sheet :color="purple800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ purple900.name }}</td>
                <td>{{ purple900.hex }}</td>
                <td>
                    <v-sheet :color="purple900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    purple50,
    purple100,
    purple200,
    purple300,
    purple400,
    purple500,
    purple600,
    purple700,
    purple800,
    purple900,
} from 'rukkiecodes-colors';
</script>
