<template>
    <h3 class="mt-10">Ocean Blue</h3>
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
                <td>{{ oceanBlue50.name }}</td>
                <td>{{ oceanBlue50.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue100.name }}</td>
                <td>{{ oceanBlue100.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue200.name }}</td>
                <td>{{ oceanBlue200.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue300.name }}</td>
                <td>{{ oceanBlue300.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue400.name }}</td>
                <td>{{ oceanBlue400.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue500.name }}</td>
                <td>{{ oceanBlue500.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue600.name }}</td>
                <td>{{ oceanBlue600.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue700.name }}</td>
                <td>{{ oceanBlue700.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue800.name }}</td>
                <td>{{ oceanBlue800.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ oceanBlue900.name }}</td>
                <td>{{ oceanBlue900.hex }}</td>
                <td>
                    <v-sheet :color="oceanBlue900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    oceanBlue50,
    oceanBlue100,
    oceanBlue200,
    oceanBlue300,
    oceanBlue400,
    oceanBlue500,
    oceanBlue600,
    oceanBlue700,
    oceanBlue800,
    oceanBlue900,
} from 'rukkiecodes-colors';
</script>
